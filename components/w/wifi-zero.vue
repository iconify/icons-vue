<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kneeq5ung.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kneeq5ung"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wifi-zero" /></template>
