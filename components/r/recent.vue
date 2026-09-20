<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1diz15bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1diz15bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:recent" /></template>
