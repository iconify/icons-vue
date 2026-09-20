<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuhln8cou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nuhln8cou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:share-1" /></template>
