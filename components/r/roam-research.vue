<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot0p-jbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot0p-jbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:roam-research" /></template>
