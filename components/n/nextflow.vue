<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdb_pibbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wdb_pibbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nextflow" /></template>
