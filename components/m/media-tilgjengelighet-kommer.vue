<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7w7fdbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7w7fdbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-tilgjengelighet-kommer" /></template>
