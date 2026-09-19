<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0sq_bx6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0sq_bx6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-left-01" /></template>
