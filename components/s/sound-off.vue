<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzxr2obon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzxr2obon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-off" /></template>
