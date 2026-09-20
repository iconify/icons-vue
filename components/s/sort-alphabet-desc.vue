<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_fwrbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er_fwrbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sort-alphabet-desc" /></template>
