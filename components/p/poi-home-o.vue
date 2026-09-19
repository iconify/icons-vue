<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsnsd8bak.css';
import '../../css/m/mce3-1bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rsnsd8bak"/><path class="mce3-1bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-home-o" /></template>
