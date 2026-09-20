<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wieq7wj0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wieq7wj0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:statom" /></template>
