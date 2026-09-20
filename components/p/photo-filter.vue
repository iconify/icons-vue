<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/foqnye_be.css';
import '../../css/z/z6d4gv1ed.css';
import '../../css/i/inqet5b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="foqnye_be"/><circle class="z6d4gv1ed"/><circle class="inqet5b8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:photo-filter" /></template>
