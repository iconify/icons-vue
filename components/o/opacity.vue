<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwn_5jwul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pwn_5jwul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:opacity" /></template>
