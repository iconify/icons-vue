<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe4_vg-gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xe4_vg-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:star-half-alt" /></template>
