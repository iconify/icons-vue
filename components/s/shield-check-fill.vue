<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk-bc8b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-bc8b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-check-fill" /></template>
