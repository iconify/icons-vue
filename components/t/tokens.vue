<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tps7xibhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tps7xibhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:tokens" /></template>
