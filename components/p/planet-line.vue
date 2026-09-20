<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltygs2q5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltygs2q5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:planet-line" /></template>
