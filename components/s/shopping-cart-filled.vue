<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xskw1ebwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xskw1ebwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shopping-cart-filled" /></template>
