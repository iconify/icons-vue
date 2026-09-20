<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mmt6z6bum.css';
import '../../css/c/cd2k4gb1a.css';
import '../../css/j/j69s81b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="mmt6z6bum"/><circle class="cd2k4gb1a"/><path class="j69s81b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:skull" /></template>
