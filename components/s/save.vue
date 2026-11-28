<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cui-ix3kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cui-ix3kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:save" /></template>
