<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijthh537c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijthh537c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rural-post-alt-outline-24px" /></template>
