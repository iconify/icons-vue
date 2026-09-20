<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkgyvebwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkgyvebwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:ruler" /></template>
