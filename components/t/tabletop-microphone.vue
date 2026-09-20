<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyjky3pmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gyjky3pmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tabletop-microphone" /></template>
