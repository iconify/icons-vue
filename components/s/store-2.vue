<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjaaedm_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kjaaedm_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:store-2" /></template>
