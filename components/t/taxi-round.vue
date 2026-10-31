<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvp1nmxes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvp1nmxes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-round" /></template>
