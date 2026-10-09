<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpac6cbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jpac6cbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-energy-converter-20" /></template>
