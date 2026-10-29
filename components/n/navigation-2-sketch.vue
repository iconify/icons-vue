<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h7w4nh9fc.css';
import '../../css/k/k-y7wkbqg.css';
import '../../css/z/z7kma4b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h7w4nh9fc"/><path class="k-y7wkbqg"/><path class="z7kma4b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-2-sketch" /></template>
