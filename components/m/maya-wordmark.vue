<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ail2dgb3l.css';
import '../../css/j/jgf7k_b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ail2dgb3l"/><path class="jgf7k_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:maya-wordmark" /></template>
