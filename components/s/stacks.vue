<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wod8oip1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wod8oip1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:stacks" /></template>
