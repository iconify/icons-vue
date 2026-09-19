<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhpymzg_r.css';
import '../../css/c/ctg85nb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhpymzg_r"/><path class="ctg85nb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snooze" /></template>
