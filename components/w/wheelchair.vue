<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-4k5kb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y-4k5kb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:wheelchair" /></template>
