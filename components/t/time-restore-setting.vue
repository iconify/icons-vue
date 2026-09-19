<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln-j0jbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":384};
const content = `<path class="ln-j0jbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:time-restore-setting" /></template>
