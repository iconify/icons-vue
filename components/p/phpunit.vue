<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__xvqzzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i__xvqzzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:phpunit" /></template>
