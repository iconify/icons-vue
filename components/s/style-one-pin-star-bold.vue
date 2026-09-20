<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmr60dzfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmr60dzfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:style-one-pin-star-bold" /></template>
