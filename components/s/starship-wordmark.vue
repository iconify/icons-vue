<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1suy98jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n1suy98jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:starship-wordmark" /></template>
