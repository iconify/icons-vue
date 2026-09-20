<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev6d5gw2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev6d5gw2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-fill" /></template>
