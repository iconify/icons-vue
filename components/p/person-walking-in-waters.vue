<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jknwspb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jknwspb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-in-waters" /></template>
