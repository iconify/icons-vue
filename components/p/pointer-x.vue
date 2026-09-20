<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj2nozalb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2nozalb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-x" /></template>
