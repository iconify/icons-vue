<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw--3tn7p.css';
import '../../css/u/ueef18k6a.css';
import '../../css/s/shu3xdl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cw--3tn7p"><path class="ueef18k6a"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:slash" /></template>
