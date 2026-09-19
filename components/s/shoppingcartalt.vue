<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-eslqfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="z2-eslqfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shoppingcartalt" /></template>
