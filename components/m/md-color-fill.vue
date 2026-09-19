<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9w0_3bdd.css';
import '../../css/g/gyiiqfa7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h9w0_3bdd"/><path class="gyiiqfa7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-color-fill" /></template>
