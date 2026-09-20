<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1k02b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1k02b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shopping-cart-filled" /></template>
