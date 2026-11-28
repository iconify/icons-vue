<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt0hurbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt0hurbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:server-x" /></template>
