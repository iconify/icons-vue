<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1bpundml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1bpundml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-cart-2-line" /></template>
