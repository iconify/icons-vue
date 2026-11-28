<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aua6iln_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aua6iln_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield" /></template>
