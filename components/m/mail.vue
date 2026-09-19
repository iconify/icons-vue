<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfa--6bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfa--6bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:mail" /></template>
