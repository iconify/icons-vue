<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv_j0tbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wv_j0tbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-settings" /></template>
