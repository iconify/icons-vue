<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk3jipkgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk3jipkgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:multiplier-2x" /></template>
