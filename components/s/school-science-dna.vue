<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsthg0bza.css';
import '../../css/p/pptl0qd1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gsthg0bza"/><path class="pptl0qd1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:school-science-dna" /></template>
