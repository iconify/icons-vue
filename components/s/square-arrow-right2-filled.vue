<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4-z_mbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4-z_mbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-right2-filled" /></template>
