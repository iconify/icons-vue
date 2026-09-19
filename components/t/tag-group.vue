<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjnq2n03l.css';
import '../../css/d/dkx4dmkzu.css';
import '../../css/t/tq0faab8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="mjnq2n03l"/><path class="dkx4dmkzu"/><path class="tq0faab8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag-group" /></template>
