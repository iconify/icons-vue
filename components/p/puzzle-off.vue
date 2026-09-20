<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkdegh_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkdegh_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:puzzle-off" /></template>
