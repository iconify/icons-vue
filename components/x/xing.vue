<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwp02941m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwp02941m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:xing" /></template>
