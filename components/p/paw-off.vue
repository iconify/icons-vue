<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btk6q5xzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btk6q5xzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paw-off" /></template>
