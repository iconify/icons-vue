<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5pgg5kgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5pgg5kgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-off-fill" /></template>
