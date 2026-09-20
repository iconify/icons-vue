<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7o009b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t7o009b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-button-computer-mouse-with-scroll-wheel" /></template>
