<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uypib39ja.css';
import '../../css/i/imes1f47p.css';
import '../../css/n/nh26eqbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="uypib39ja"><path class="imes1f47p"/><path class="nh26eqbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:solidity" /></template>
