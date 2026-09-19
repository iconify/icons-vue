<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzwv2ebuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dzwv2ebuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shopping-basket" /></template>
