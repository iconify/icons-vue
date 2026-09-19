<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltlf2ibuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ltlf2ibuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:swarm" /></template>
