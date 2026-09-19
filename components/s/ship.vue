<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw0xofbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw0xofbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:ship" /></template>
