<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9i2nublj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p9i2nublj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:stop" /></template>
