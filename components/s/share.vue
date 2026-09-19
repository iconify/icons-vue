<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl5pawb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hl5pawb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:share" /></template>
