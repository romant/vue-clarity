<template>
  <div id="app">
    <button class="btn">Regular</button>
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-success">Success</button>
    <button class="btn btn-info">Info</button>
    <button class="btn btn-warning">Warning</button>
    <button class="btn btn-danger">Danger</button>
    <button class="btn" disabled>Disabled</button>

    <button type="button" class="btn btn-icon">
    <clr-icon shape="home"></clr-icon>
    </button>
    <button type="button" class="btn btn-icon btn-primary">
        <clr-icon shape="cog"></clr-icon>
    </button>
    <button type="button" class="btn btn-icon btn-warning">
        <clr-icon shape="warning-standard"></clr-icon>
    </button>
    <button type="button" class="btn btn-icon btn-danger">
        <clr-icon shape="error-standard"></clr-icon>
    </button>
    <button type="button" class="btn btn-icon btn-success">
        <clr-icon shape="check"></clr-icon>
    </button>
    <button type="button" class="btn btn-icon" disabled>
        <clr-icon shape="home"></clr-icon>
    </button>

    <clr-icon shape="info-circle" size="12"></clr-icon>
    <clr-icon shape="info-circle" size="16"></clr-icon>
    <clr-icon shape="info-circle" size="36"></clr-icon>
    <clr-icon shape="info-circle" size="48"></clr-icon>
    <clr-icon shape="info-circle" size="64"></clr-icon>
    <clr-icon shape="info-circle" size="72"></clr-icon>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

import "@clr/ui/clr-ui.css";
import '@clr/icons';
import '@clr/icons/shapes/all-shapes';

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>

</style>
