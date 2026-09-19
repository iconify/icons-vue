<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l859wrbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l859wrbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:polygon" /></template>
