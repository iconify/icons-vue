<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqd17fbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqd17fbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reading" /></template>
