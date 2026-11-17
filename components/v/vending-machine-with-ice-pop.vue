<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6opc0buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n6opc0buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-ice-pop" /></template>
