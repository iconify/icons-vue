<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx118f5my.css';
import '../../css/b/btb61zlai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx118f5my"/><path class="btb61zlai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-1-line" /></template>
