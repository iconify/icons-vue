<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfks5kbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfks5kbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sack-percent" /></template>
