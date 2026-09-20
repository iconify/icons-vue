<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkgo5nbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkgo5nbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-search" /></template>
