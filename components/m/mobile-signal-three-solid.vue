<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fucn8nbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fucn8nbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile-signal-three-solid" /></template>
