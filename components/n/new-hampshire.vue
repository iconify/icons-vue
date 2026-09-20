<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kglmfhmmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kglmfhmmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:new-hampshire" /></template>
