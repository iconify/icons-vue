<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svrtpbcxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svrtpbcxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:vertical-top" /></template>
