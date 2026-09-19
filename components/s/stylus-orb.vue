<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyo5l_bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyo5l_bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stylus-orb" /></template>
