<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn9u4w0zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hn9u4w0zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:map-pin-slash" /></template>
