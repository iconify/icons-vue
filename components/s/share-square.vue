<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8g5bw7_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="u8g5bw7_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:share-square" /></template>
