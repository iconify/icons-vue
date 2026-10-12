<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfcc4qbni.css';
import '../../css/y/ym-zwb07i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcc4qbni"/><path class="ym-zwb07i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-cart-plus-filled" /></template>
