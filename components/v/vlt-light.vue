<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaebqy2hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":175};
const content = `<path class="vaebqy2hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vlt-light" /></template>
