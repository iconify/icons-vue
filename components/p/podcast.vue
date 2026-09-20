<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spa_k7f-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spa_k7f-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:podcast" /></template>
