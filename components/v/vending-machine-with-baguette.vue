<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl4nbbbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vl4nbbbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-baguette" /></template>
