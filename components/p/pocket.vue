<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lu_t7nbma.css';
import '../../css/a/a5ita3bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="lu_t7nbma"/><path class="a5ita3bje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:pocket" /></template>
