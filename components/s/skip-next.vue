<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvpkib4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="gwvpkib4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:skip-next" /></template>
