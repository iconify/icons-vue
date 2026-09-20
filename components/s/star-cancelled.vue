<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k96n5jw4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k96n5jw4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-cancelled" /></template>
