<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bct70fbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bct70fbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:person-plus" /></template>
