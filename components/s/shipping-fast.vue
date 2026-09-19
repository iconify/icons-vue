<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jon4cnb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="jon4cnb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shipping-fast" /></template>
