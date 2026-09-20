<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g307o3kzp.css';
import '../../css/u/ubccq2blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g307o3kzp"/><path class="ubccq2blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sofe" /></template>
