<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6ioh9qho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6ioh9qho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-vert-fill" /></template>
