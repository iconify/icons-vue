<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2i32kysp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2i32kysp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trello" /></template>
