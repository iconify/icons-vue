<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o3zs0wwrm.css';
import '../../css/j/jo0n1h6-a.css';
import '../../css/t/t-ngn6b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o3zs0wwrm"/><path class="jo0n1h6-a"/><path class="t-ngn6b1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:popcorn" /></template>
