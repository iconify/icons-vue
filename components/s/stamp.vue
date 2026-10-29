<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/r/r9ee07b4q.css';
import '../../css/m/mo4d7k32t.css';
import '../../css/c/cbq31zbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="r9ee07b4q wm-k"/><path class="mo4d7k32t wm-a"/><path class="cbq31zbeo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:stamp" /></template>
