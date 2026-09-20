<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vne-oq9_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="vne-oq9_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:shoppingcart" /></template>
