<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdl0eybov.css';
import '../../css/z/z1aoycclw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jdl0eybov"/><path class="z1aoycclw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchguard" /></template>
