<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svy-d9glg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svy-d9glg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:shopping-cart-02" /></template>
