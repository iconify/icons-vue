<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axxv63syb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axxv63syb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tag-solid" /></template>
