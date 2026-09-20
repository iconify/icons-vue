<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7vmbpvxl.css';
import '../../css/f/flopf26xs.css';
import '../../css/g/gra5yw4ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="e7vmbpvxl"/><path class="flopf26xs"/><path class="gra5yw4ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortarr-dark" /></template>
