<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb8kicbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb8kicbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-line" /></template>
