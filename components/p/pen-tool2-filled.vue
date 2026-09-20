<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgsmusb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgsmusb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen-tool2-filled" /></template>
