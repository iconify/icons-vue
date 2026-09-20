<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2wr9wc8g.css';
import '../../css/n/nn222kb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l2wr9wc8g"/><path class="nn222kb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openal" /></template>
