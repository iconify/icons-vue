<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdbdfdbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdbdfdbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sort-ascending" /></template>
