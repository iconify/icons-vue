<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr9k79o_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr9k79o_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-no-signal" /></template>
