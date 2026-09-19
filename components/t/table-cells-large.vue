<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kid_kqb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kid_kqb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:table-cells-large" /></template>
