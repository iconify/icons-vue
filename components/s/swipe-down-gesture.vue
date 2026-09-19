<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ufj2b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ufj2b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-down-gesture" /></template>
