<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6---bwut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6---bwut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:virus" /></template>
