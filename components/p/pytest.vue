<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z63w88byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z63w88byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pytest" /></template>
