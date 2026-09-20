<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr31whbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fr31whbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:rectangle-2" /></template>
