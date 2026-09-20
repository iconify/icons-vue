<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ibfrbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ibfrbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-quote-sharp" /></template>
