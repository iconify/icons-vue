<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcif0d1_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcif0d1_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:scooter-3-bold" /></template>
