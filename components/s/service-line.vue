<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tizcz3suw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tizcz3suw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:service-line" /></template>
