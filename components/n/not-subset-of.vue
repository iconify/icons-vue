<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4akcoble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4akcoble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:not-subset-of" /></template>
