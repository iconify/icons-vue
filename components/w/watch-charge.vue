<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_op9ivop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_op9ivop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:watch-charge" /></template>
