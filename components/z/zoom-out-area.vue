<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_g6hekil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_g6hekil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-out-area" /></template>
