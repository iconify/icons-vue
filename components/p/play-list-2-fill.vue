<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugdzc4kwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugdzc4kwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-list-2-fill" /></template>
