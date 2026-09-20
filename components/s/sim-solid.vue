<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iywas_9tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="iywas_9tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sim-solid" /></template>
