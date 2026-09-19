<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr19c78yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hr19c78yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:rupiah-sign" /></template>
