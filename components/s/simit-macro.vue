<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpwa63brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fpwa63brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:simit-macro" /></template>
