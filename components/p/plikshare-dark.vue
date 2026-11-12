<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdv9p3brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdv9p3brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plikshare-dark" /></template>
