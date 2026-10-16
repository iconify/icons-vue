<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poxn7fb3x.css';
import '../../css/h/h4vfp4baj.css';
import '../../css/p/p6isisbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="poxn7fb3x"/><path class="h4vfp4baj"/><path class="p6isisbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transition-piece-20-bold" /></template>
