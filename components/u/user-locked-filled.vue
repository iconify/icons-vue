<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3s7w-bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3s7w-bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-locked-filled" /></template>
