<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykintebag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykintebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ribbon" /></template>
