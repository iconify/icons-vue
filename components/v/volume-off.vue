<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb8mwcbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb8mwcbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:volume-off" /></template>
