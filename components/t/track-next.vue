<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6bnuccvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6bnuccvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:track-next" /></template>
