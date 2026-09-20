<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tudvt2bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tudvt2bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:researcherid-square" /></template>
