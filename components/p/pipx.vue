<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsbyav3kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbyav3kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pipx" /></template>
