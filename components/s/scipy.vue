<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgxftsb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgxftsb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:scipy" /></template>
