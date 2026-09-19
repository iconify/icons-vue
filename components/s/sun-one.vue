<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cny4agblb.css';
import '../../css/a/ad1pplybg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cny4agblb"/><path class="ad1pplybg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sun-one" /></template>
