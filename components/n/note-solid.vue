<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tne5lpbaz.css';
import '../../css/t/tylyzabts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tne5lpbaz"/><path class="tylyzabts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:note-solid" /></template>
