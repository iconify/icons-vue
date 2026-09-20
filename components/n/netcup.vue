<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgrr25wcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgrr25wcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:netcup" /></template>
