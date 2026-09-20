<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-cqv87wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cqv87wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:victoriametrics" /></template>
