<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0rcf4lyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0rcf4lyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:square" /></template>
