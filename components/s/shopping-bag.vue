<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0827ujmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0827ujmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:shopping-bag" /></template>
