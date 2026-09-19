<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke2tg-bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ke2tg-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni5475-box" /></template>
