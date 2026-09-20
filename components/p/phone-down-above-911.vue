<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-q25bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kj-q25bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-down-above-911" /></template>
