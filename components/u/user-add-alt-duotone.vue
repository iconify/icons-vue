<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d0am46jmx.css';
import '../../css/b/bdi5cobhw.css';
import '../../css/q/qjwupbcdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="d0am46jmx"/><path clip-rule="evenodd" class="bdi5cobhw"/><path class="qjwupbcdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-add-alt-duotone" /></template>
