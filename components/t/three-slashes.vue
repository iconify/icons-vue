<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinuwhlnp.css';
import '../../css/f/fe76870ub.css';
import '../../css/k/kn3ze0bti.css';
import '../../css/c/c3lurtbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="fe76870ub"/><path class="kn3ze0bti"/><path class="c3lurtbix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:three-slashes" /></template>
