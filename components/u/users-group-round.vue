<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq8r0ildq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8r0ildq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-group-round" /></template>
