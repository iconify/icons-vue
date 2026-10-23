<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q87ez3nph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q87ez3nph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scissors" /></template>
