<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6t5k5bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6t5k5bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-left2-filled" /></template>
