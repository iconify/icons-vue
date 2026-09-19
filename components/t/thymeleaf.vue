<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/humzy5bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="humzy5bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:thymeleaf" /></template>
