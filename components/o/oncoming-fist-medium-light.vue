<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1csdzbsc.css';
import '../../css/b/brktsgbib.css';
import '../../css/t/tr8rqmbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l1csdzbsc"/><path class="brktsgbib"/><path class="tr8rqmbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:oncoming-fist-medium-light" /></template>
