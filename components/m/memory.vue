<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7-al5b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n7-al5b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:memory" /></template>
