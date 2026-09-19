<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y50eh9b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="y50eh9b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shoppingcart" /></template>
