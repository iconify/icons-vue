<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl4hzbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfl4hzbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mouse" /></template>
