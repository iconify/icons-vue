<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv59zrbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fv59zrbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-ticket" /></template>
