<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr0zt0kgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr0zt0kgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:quote-left" /></template>
