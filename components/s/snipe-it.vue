<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idd-aow3o.css';
import '../../css/w/w45w5fwan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":140.2,"height":144.6,"left":66.9,"top":58.4};
const content = `<path class="idd-aow3o"/><path class="w45w5fwan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:snipe-it" /></template>
