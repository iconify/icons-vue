<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz9aracnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kz9aracnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:nine-of-characters-mahjong" /></template>
