<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4e3b0h7s.css';
import '../../css/x/x0u-ch0td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4e3b0h7s"/><path class="x0u-ch0td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-bag-2" /></template>
