<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_p6bmic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_p6bmic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parentheses-fill" /></template>
