<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7gofpb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7gofpb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:venus" /></template>
