<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn7-o7nhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dn7-o7nhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:timer" /></template>
