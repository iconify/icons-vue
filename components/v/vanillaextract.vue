<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q57lwbc9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q57lwbc9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vanillaextract" /></template>
