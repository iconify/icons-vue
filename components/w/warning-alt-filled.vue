<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o605f_yot.css';
import '../../css/c/ce7aadsur.css';
import '../../css/w/wczsurb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o605f_yot"/><path class="ce7aadsur"/><path class="wczsurb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-alt-filled" /></template>
