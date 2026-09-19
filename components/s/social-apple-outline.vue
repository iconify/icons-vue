<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so0eo1u0h.css';
import '../../css/v/vb_z8ebaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so0eo1u0h"/><path class="vb_z8ebaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-apple-outline" /></template>
