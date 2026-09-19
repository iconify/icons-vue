<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/ihqvv61nw.css';
import '../../css/e/evhc4ehqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="trending-up-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ihqvv61nw"/><path class="evhc4ehqx"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:trending-up-outline" /></template>
