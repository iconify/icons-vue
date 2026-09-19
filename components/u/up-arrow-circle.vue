<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twgo94b6k.css';
import '../../css/b/bc0bc3bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twgo94b6k"/><path class="bc0bc3bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:up-arrow-circle" /></template>
