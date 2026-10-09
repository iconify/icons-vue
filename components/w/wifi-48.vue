<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s31pbgi7y.css';
import '../../css/m/mxan4gp1r.css';
import '../../css/v/vp9gn9sho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s31pbgi7y"/><path class="mxan4gp1r"/><path class="vp9gn9sho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-48" /></template>
