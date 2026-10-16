<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewk2or1yh.css';
import '../../css/v/vuc2o48vf.css';
import '../../css/u/uofloxbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewk2or1yh"/><path class="vuc2o48vf"/><path class="uofloxbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-bulb-20" /></template>
