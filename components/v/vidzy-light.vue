<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv9fipb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gv9fipb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vidzy-light" /></template>
