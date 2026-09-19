<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ejwlimo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ejwlimo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:wind" /></template>
