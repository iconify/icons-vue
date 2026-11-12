<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsp5zr9ng.css';
import '../../css/b/bbjq83b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nsp5zr9ng"/><path class="bbjq83b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailpit" /></template>
