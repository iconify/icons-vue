<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-n2j-byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w-n2j-byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:university" /></template>
