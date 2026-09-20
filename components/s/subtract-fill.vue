<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf2dj6b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf2dj6b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:subtract-fill" /></template>
