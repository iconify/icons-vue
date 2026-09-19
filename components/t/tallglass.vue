<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hczb_fq6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":1024};
const content = `<path class="hczb_fq6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tallglass" /></template>
