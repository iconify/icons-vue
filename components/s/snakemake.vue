<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai6onkxos.css';
import '../../css/p/puojo9i0c.css';
import '../../css/w/wd2296cyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ai6onkxos"/><path class="puojo9i0c"/><path class="wd2296cyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:snakemake" /></template>
