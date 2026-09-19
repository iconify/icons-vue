<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sujvg4r4g.css';
import '../../css/x/xijg6zb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sujvg4r4g"/><path class="xijg6zb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:package" /></template>
