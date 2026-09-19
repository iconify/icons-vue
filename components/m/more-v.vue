<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzvafrbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":5,"height":24};
const content = `<path class="zzvafrbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:more-v" /></template>
