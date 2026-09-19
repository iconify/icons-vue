<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw67gzbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw67gzbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trees" /></template>
