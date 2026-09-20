<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjixjmliq.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/slyvoxbel.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGZ3M9fe9k" class="bjixjmliq"/></defs><g class="cuyn6tgcc"><path clip-rule="evenodd" class="slyvoxbel"/><use href="#SVGZ3M9fe9k" clip-rule="evenodd" class="d2kvgvbvc"/><use href="#SVGZ3M9fe9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-cloud-filled" /></template>
