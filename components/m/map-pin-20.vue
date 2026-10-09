<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9cx5cc5b.css';
import '../../css/l/lmjbu-ywi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9cx5cc5b"/><path class="lmjbu-ywi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-pin-20" /></template>
