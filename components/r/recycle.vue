<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/b/bi1v6bb7h.css';
import '../../css/r/rt2nribcm.css';
import '../../css/k/klvcus7uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="bi1v6bb7h"/><path class="rt2nribcm"/><path class="klvcus7uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:recycle" /></template>
