<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjy069u9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjy069u9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:trophy-line" /></template>
