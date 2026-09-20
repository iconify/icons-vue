<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyb0-gxmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyb0-gxmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pokemon" /></template>
