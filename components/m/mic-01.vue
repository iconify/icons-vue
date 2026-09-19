<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8awi8bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8awi8bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mic-01" /></template>
