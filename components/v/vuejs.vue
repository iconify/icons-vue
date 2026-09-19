<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iojqet6kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iojqet6kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vuejs" /></template>
