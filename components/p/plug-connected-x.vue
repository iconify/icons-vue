<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2ebknbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ebknbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:plug-connected-x" /></template>
