<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh6xk1tzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh6xk1tzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:nutrition" /></template>
