<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qchdvmbcp.css';
import '../../css/c/cwo24bbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qchdvmbcp"/><path class="cwo24bbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-line" /></template>
