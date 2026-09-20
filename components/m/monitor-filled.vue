<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgisqnb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgisqnb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:monitor-filled" /></template>
