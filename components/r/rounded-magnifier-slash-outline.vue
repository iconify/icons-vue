<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a501rabcl.css';
import '../../css/n/n_sy2m0fq.css';
import '../../css/p/ppn0rybgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a501rabcl"/><path class="n_sy2m0fq"/><path clip-rule="evenodd" class="ppn0rybgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-slash-outline" /></template>
