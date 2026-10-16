<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx2djpbfz.css';
import '../../css/p/p2ofzxv5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="p2ofzxv5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-crescent-20-bold" /></template>
