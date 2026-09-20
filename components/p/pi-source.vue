<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stc4fdcup.css';
import '../../css/k/k370xsb9r.css';
import '../../css/h/hdfgeqb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="stc4fdcup"/><path class="k370xsb9r"/><path class="hdfgeqb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-source" /></template>
