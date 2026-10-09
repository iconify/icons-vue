<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmp784cfc.css';
import '../../css/d/d6khf1dib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mmp784cfc"/><path class="d6khf1dib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spatula-20" /></template>
