<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxrp5pbhu.css';
import '../../css/z/zwkxfwbcx.css';
import '../../css/j/jgecn8b8w.css';
import '../../css/s/si615ccmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="dxrp5pbhu"><path class="zwkxfwbcx"/><path class="jgecn8b8w"/></g><path class="si615ccmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:rotate-camera" /></template>
