<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhq4ynm1t.css';
import '../../css/z/zenhfcbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhq4ynm1t"/><path class="zenhfcbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:messages-20-bold" /></template>
