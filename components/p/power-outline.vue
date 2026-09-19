<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/btc0ci6jt.css';
import '../../css/n/n9i8cmbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="power-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="btc0ci6jt"/><path class="n9i8cmbmc"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:power-outline" /></template>
