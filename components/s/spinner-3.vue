<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7fumb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km7fumb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spinner-3" /></template>
