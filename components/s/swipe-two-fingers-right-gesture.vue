<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knl5nbbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knl5nbbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-two-fingers-right-gesture" /></template>
