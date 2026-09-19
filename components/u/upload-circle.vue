<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w11gdab4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w11gdab4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:upload-circle" /></template>
