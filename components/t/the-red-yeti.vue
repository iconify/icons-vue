<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc5aw5fhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc5aw5fhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:the-red-yeti" /></template>
