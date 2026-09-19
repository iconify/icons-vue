<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2ot_552a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g2ot_552a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-rubl-circle" /></template>
