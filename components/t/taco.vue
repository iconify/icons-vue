<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h80q1pbzw.css';
import '../../css/a/a-pyxqjuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h80q1pbzw"/><path class="a-pyxqjuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:taco" /></template>
