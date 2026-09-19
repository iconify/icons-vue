<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdsw_ab7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="xdsw_ab7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pied-piper-pp" /></template>
