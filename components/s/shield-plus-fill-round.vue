<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxj0mf-xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxj0mf-xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-plus-fill-round" /></template>
