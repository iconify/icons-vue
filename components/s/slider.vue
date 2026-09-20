<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nym9eib8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nym9eib8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:slider" /></template>
