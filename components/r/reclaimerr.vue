<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz0_h5o9w.css';
import '../../css/a/adkjrqbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jz0_h5o9w"/><path class="adkjrqbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reclaimerr" /></template>
