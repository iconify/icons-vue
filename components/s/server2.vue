<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq5e5r7xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq5e5r7xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server2" /></template>
