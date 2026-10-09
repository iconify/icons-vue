<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alp85pbpf.css';
import '../../css/o/o3nn0j39f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="alp85pbpf"/><path class="o3nn0j39f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pram-20-bold" /></template>
