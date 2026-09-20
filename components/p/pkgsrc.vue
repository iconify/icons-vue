<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv19rdkrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv19rdkrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pkgsrc" /></template>
