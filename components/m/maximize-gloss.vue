<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wteyjubfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wteyjubfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-gloss" /></template>
