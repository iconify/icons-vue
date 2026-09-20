<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uevmlbz-z.css';
import '../../css/s/swaugsbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uevmlbz-z"/><path class="swaugsbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wireless-1-16" /></template>
