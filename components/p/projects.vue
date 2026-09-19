<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw64g_bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw64g_bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:projects" /></template>
