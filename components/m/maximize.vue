<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ianmb7bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ianmb7bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:maximize" /></template>
