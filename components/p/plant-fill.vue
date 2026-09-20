<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4w57mipq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4w57mipq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:plant-fill" /></template>
