<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trsg9gb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsg9gb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:stop" /></template>
