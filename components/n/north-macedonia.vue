<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gktr6dbvg.css';
import '../../css/f/fr0bdx4ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="gktr6dbvg"/><path class="fr0bdx4ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:north-macedonia" /></template>
