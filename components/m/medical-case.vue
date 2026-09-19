<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5l9kaceg.css';
import '../../css/w/wao3ae53h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5l9kaceg"/><path class="wao3ae53h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:medical-case" /></template>
