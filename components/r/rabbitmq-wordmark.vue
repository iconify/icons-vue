<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u86l3ccfz.css';
import '../../css/b/b8bh25bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u86l3ccfz"/><path class="b8bh25bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rabbitmq-wordmark" /></template>
