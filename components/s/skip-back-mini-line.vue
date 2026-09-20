<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm3h6bb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm3h6bb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-back-mini-line" /></template>
