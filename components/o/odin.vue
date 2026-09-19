<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgg1rqb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sgg1rqb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:odin" /></template>
