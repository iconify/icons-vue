<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsu6aob7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wsu6aob7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:upload-circle-fill" /></template>
