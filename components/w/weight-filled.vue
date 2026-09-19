<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bioodsb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bioodsb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:weight-filled" /></template>
