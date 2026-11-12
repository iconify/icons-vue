<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p75du9kle.css';
import '../../css/f/f08bsp95i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p75du9kle"/><path class="f08bsp95i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piped-light" /></template>
