<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32f_itun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h32f_itun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mercurial-wordmark" /></template>
