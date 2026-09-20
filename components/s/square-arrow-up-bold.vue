<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st1-uurhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st1-uurhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-up-bold" /></template>
