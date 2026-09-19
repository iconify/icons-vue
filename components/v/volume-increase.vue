<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir5hywcvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ir5hywcvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:volume-increase" /></template>
