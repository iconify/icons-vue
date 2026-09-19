<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we63e0kfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="we63e0kfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:suit-heart" /></template>
