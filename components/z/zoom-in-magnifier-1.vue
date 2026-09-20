<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-ess6cm.css';
import '../../css/h/h5ci0qb1w.css';
import '../../css/f/fd5oc7b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq-ess6cm"/><path class="h5ci0qb1w"/><path class="fd5oc7b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:zoom-in-magnifier-1" /></template>
