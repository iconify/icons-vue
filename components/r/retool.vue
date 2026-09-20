<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eodtv5b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eodtv5b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:retool" /></template>
