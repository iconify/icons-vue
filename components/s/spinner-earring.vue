<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eldv-d4uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eldv-d4uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:spinner-earring" /></template>
