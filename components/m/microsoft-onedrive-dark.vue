<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzxu6cbem.css';
import '../../css/y/y5x_dib_i.css';
import '../../css/b/b6edkyxdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzxu6cbem"/><path class="y5x_dib_i"/><path class="b6edkyxdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-onedrive-dark" /></template>
