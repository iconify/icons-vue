<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b8ncf6bzy.css';
import '../../css/d/d_niiab4v.css';
import '../../css/f/f72ylivjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b8ncf6bzy"/><path class="d_niiab4v"/><path class="f72ylivjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scroll-duotone" /></template>
