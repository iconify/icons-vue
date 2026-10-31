<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvq7y5bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvq7y5bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-2-gloss" /></template>
