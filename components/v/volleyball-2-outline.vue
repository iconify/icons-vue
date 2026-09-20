<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_p5dbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ty_p5dbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volleyball-2-outline" /></template>
