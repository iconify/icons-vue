<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jjw62pbsu.css';
import '../../css/p/pn-wogbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="user-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="jjw62pbsu"/><path class="pn-wogbiq"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:user-outline" /></template>
