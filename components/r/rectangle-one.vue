<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkqie5bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkqie5bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rectangle-one" /></template>
