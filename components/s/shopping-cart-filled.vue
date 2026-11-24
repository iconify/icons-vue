<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2hrev5_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2hrev5_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-cart-filled" /></template>
