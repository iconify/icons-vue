<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18qyszxk.css';
import '../../css/c/cwaoh8bpd.css';
import '../../css/n/nrw-6wbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c18qyszxk"/><path class="cwaoh8bpd"/><path class="nrw-6wbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:puppeteer" /></template>
