<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uww47e16f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uww47e16f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:send-alt-02-filled" /></template>
