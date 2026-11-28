<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxmfwqbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmfwqbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-square" /></template>
