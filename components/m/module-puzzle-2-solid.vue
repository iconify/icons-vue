<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq3wg0bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xq3wg0bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:module-puzzle-2-solid" /></template>
