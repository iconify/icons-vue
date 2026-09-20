<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twu4h7bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twu4h7bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:popcorn" /></template>
