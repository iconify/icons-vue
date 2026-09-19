<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7zrlbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="hu7zrlbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-paused" /></template>
