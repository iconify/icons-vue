<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5v5k58ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t5v5k58ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:person-pencil-fill-20" /></template>
