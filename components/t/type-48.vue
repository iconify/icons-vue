<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_yfmnbkd.css';
import '../../css/y/ya6awqbqs.css';
import '../../css/z/zu-vrnrjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_yfmnbkd"/><path class="ya6awqbqs"/><path class="zu-vrnrjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:type-48" /></template>
