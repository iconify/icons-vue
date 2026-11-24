<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfcc4qbni.css';
import '../../css/m/mpy22xgmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfcc4qbni"/><path class="mpy22xgmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-cart-plus-filled" /></template>
