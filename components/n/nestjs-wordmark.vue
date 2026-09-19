<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmw9lxb9g.css';
import '../../css/n/n8mc1xbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pmw9lxb9g"/><path class="n8mc1xbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nestjs-wordmark" /></template>
