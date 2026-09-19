<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u71pldtly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u71pldtly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:traffic-cone" /></template>
