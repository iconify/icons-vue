<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xixjqkb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xixjqkb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:success-filled" /></template>
