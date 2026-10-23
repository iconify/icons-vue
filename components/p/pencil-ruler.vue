<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbjc9sb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbjc9sb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil-ruler" /></template>
