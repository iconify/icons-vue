<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvq-sy4sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvq-sy4sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:speed-fill" /></template>
