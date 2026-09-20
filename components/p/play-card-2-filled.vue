<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-q_sb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-q_sb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-2-filled" /></template>
