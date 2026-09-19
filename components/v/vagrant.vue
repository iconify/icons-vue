<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj4p5eb8q.css';
import '../../css/n/nm2y6cbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pj4p5eb8q"/><path class="nm2y6cbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vagrant" /></template>
