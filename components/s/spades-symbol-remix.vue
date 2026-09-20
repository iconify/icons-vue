<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-ck-kbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g-ck-kbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spades-symbol-remix" /></template>
