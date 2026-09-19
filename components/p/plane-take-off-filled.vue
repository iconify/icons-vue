<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3p65ddzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3p65ddzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plane-take-off-filled" /></template>
