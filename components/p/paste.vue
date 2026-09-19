<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jre1oib0e.css';
import '../../css/v/vdbqspb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jre1oib0e"/><path class="vdbqspb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:paste" /></template>
