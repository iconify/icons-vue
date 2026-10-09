<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkm6ueyhw.css';
import '../../css/r/rdt8hgb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tkm6ueyhw"/><path class="rdt8hgb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-bottle-20" /></template>
