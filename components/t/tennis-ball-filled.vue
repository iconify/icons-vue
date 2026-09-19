<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvi2gab-r.css';
import '../../css/t/tctjssbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvi2gab-r"/><path class="tctjssbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis-ball-filled" /></template>
