<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-q9qbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-q9qbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mojeek" /></template>
