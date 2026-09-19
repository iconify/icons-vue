<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3bhmacip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="x3bhmacip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sex-male" /></template>
