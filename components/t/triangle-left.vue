<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mthpz1b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mthpz1b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-left" /></template>
