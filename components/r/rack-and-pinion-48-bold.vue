<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8spygx2w.css';
import '../../css/f/fkn2szbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8spygx2w"/><path class="fkn2szbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rack-and-pinion-48-bold" /></template>
