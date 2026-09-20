<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbny_actr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pbny_actr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:triangle-flag-solid" /></template>
