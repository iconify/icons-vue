<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5g4gdxon.css';
import '../../css/c/c-2y_lb8w.css';
import '../../css/f/fpx2kva1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b5g4gdxon"/><path class="c-2y_lb8w"/><path class="fpx2kva1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plumb-bob-20" /></template>
