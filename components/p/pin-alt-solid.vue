<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff9amtfnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ff9amtfnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pin-alt-solid" /></template>
