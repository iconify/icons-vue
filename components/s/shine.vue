<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyngsypel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyngsypel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:shine" /></template>
