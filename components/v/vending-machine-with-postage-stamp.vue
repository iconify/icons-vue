<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8t3jxb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f8t3jxb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-postage-stamp" /></template>
