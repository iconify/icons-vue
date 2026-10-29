<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/m/mevgakb8a.css';
import '../../css/f/ftmmgybqo.css';
import '../../css/s/szy4bhbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="mevgakb8a"/><path class="ftmmgybqo"/><path class="szy4bhbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:radar" /></template>
