<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnbbjbbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnbbjbbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:seagate" /></template>
