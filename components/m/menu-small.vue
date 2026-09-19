<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6v6--uhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t6v6--uhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:menu-small" /></template>
