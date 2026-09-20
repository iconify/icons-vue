<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sik-0kbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sik-0kbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:matternet" /></template>
