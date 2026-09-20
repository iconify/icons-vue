<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps6tg9bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ps6tg9bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mobile-phone-with-touchscreen-and-antenna" /></template>
