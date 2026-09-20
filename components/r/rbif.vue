<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r90j-2b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r90j-2b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rbif" /></template>
