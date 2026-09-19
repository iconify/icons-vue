<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7zbqmbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k7zbqmbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:musical-score" /></template>
