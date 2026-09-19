<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvrle7lfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hvrle7lfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:wasi" /></template>
