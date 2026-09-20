<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9632hb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9632hb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus" /></template>
