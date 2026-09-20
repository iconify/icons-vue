<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thqiy6l0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thqiy6l0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-waves-solid" /></template>
