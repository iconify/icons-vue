<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx-k5ebuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dx-k5ebuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pin" /></template>
