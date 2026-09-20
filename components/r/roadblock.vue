<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm3dusb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gm3dusb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:roadblock" /></template>
