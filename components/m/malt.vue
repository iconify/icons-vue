<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtw-06s3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtw-06s3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:malt" /></template>
