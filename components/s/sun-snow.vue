<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0vo_rj-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0vo_rj-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sun-snow" /></template>
