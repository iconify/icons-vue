<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdui42b6r.css';
import '../../css/j/j6e6uqpop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jdui42b6r"/><path class="j6e6uqpop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:money-bag-20-bold" /></template>
