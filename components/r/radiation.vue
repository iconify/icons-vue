<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu5p79zwm.css';
import '../../css/l/l34qd19yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bu5p79zwm"/><path class="l34qd19yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:radiation" /></template>
