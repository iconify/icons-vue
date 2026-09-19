<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1m_geb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="h1m_geb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:users-rays" /></template>
