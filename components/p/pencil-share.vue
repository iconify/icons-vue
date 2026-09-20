<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylkhpkk2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylkhpkk2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-share" /></template>
