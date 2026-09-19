<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ve_51rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y7ve_51rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:scissors-alt" /></template>
