<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcr26mbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcr26mbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wave-square" /></template>
