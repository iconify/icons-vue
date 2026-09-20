<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijd016b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijd016b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-rotate" /></template>
