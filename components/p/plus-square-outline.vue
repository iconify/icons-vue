<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7s6tsbkb.css';
import '../../css/j/jzowd3bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s6tsbkb"/><path class="jzowd3bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:plus-square-outline" /></template>
