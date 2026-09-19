<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utg5x7c1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utg5x7c1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:vector-square" /></template>
