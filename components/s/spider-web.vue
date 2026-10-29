<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/in2j8iy9x.css';
import '../../css/a/apd15e1-n.css';
import '../../css/g/glpi5abzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="in2j8iy9x"/><path class="apd15e1-n"/><path class="glpi5abzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:spider-web" /></template>
