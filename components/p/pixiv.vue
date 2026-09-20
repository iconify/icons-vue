<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o00yobsfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o00yobsfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pixiv" /></template>
