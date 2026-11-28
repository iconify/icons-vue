<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o99x5v3qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o99x5v3qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-4" /></template>
