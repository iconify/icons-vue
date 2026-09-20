<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-cyvkb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r-cyvkb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:pin-top" /></template>
