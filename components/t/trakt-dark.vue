<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hct-yyznp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hct-yyznp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trakt-dark" /></template>
