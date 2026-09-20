<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu3ddzb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu3ddzb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-off" /></template>
