<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqep3ob2t.css';
import '../../css/p/pvryphb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqep3ob2t"/><path class="pvryphb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seaweed-48-bold" /></template>
