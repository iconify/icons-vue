<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnrbw7e8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnrbw7e8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:shopping-cart" /></template>
