<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twu1jgkwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twu1jgkwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-code-filled" /></template>
