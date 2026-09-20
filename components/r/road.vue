<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk7-0nbwz.css';
import '../../css/l/lyrbudsuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fk7-0nbwz"/><path class="lyrbudsuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:road" /></template>
