<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nflt8sfxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nflt8sfxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:triangles-left-right" /></template>
