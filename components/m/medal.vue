<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh5xl2syl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh5xl2syl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:medal" /></template>
