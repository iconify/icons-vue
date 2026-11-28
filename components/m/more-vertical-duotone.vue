<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g25yvtc_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g25yvtc_t primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:more-vertical-duotone" /></template>
