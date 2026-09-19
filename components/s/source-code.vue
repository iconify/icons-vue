<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arew0hbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arew0hbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:source-code" /></template>
