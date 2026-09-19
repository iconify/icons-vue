<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tklj3wb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tklj3wb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-rows-split" /></template>
