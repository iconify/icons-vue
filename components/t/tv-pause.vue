<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzplro11u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzplro11u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tv-pause" /></template>
