<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6jwrd_9i.css';
import '../../css/f/ffi2c7jam.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 u6jwrd_9i"/><circle class="clr-i-solid clr-i-solid-path-2 ffi2c7jam"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:map-marker-solid" /></template>
