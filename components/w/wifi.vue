<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx7mb-bib.css';
import '../../css/z/zapq_sb9r.css';
import '../../css/y/y_knajrym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7mb-bib"/><path class="zapq_sb9r"/><path class="y_knajrym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wifi" /></template>
