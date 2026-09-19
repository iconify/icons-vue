<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiedn7oku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiedn7oku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tape" /></template>
