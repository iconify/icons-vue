<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7pm7ncvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f7pm7ncvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mdao" /></template>
