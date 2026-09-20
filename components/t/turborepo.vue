<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjtv-0f9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtv-0f9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:turborepo" /></template>
