<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lga-v6l8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lga-v6l8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:patreon-outline" /></template>
