<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7czz_6xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7czz_6xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zdf" /></template>
