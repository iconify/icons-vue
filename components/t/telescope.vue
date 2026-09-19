<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voupb981m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="voupb981m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:telescope" /></template>
