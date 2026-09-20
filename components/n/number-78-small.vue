<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc2i8mbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc2i8mbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-78-small" /></template>
