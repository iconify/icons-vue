<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxts3kbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="jxts3kbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:volume-off" /></template>
