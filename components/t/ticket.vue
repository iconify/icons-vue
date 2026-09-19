<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu7_tkyee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu7_tkyee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:ticket" /></template>
