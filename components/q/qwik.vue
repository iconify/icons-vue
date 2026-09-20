<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8aw24b0h.css';
import '../../css/t/tnv3g-b3r.css';
import '../../css/c/cduhi3biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8aw24b0h"/><path class="tnv3g-b3r"/><path class="cduhi3biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qwik" /></template>
