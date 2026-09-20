<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipf2zhprn.css';
import '../../css/c/cvimsccvy.css';
import '../../css/i/i5lmhc31t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ipf2zhprn"/><path class="cvimsccvy"/><path class="i5lmhc31t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:upload" /></template>
