<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tny0wxbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tny0wxbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shopping-cart-outline" /></template>
