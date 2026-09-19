<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdt6ofbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdt6ofbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:play-backwards" /></template>
