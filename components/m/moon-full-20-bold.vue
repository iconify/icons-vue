<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx2djpbfz.css';
import '../../css/m/m1or6kb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tx2djpbfz"/><path class="m1or6kb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-full-20-bold" /></template>
