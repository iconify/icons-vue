<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9skdhbhr.css';
import '../../css/m/mg5nb2b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q9skdhbhr"/><path class="mg5nb2b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:swagger-wordmark" /></template>
