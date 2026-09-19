<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimb9pjdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bimb9pjdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:weight" /></template>
