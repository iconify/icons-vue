<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy6ak9tth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gy6ak9tth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-shelves" /></template>
