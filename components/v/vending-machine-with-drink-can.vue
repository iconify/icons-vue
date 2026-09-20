<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqt3l_bdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gqt3l_bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-drink-can" /></template>
