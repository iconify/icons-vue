<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr8svymbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr8svymbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:route-gloss" /></template>
