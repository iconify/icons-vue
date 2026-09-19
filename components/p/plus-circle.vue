<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-wsp12n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl-wsp12n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:plus-circle" /></template>
