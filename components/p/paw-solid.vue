<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxngbs5rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sxngbs5rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paw-solid" /></template>
