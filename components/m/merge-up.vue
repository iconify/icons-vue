<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd1m31bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1m31bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:merge-up" /></template>
