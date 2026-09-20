<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay7ptcczs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay7ptcczs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:substack" /></template>
