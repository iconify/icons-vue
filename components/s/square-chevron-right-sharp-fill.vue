<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geki3y6gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geki3y6gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-right-sharp-fill" /></template>
