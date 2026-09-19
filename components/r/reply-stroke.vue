<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsnyt7lwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsnyt7lwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reply-stroke" /></template>
