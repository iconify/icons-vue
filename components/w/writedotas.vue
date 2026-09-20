<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlfven3ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlfven3ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:writedotas" /></template>
