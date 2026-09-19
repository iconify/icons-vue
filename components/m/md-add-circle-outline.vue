<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxds-kb_t.css';
import '../../css/m/moox_lvwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxds-kb_t"/><path class="moox_lvwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-add-circle-outline" /></template>
