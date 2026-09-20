<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1mc5lbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a1mc5lbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-square" /></template>
