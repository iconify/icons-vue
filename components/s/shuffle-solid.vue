<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te6x4btrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te6x4btrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shuffle-solid" /></template>
