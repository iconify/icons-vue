<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzyx-5b6c.css';
import '../../css/w/w_klxbu6c.css';
import '../../css/e/ez_4otvdt.css';
import '../../css/x/xu4n-p7uu.css';
import '../../css/n/nahlbrvea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="pzyx-5b6c"/><path class="w_klxbu6c"/><path class="ez_4otvdt"/><path class="xu4n-p7uu"/><path class="nahlbrvea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:soccer-ball" /></template>
