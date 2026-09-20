<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykg-_fbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ykg-_fbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-ix" /></template>
