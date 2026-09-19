<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdoy8tbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdoy8tbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sign-language-c" /></template>
