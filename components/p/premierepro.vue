<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltghsnbbc.css';
import '../../css/s/spcgr69nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ltghsnbbc"/><path class="spcgr69nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:premierepro" /></template>
