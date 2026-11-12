<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8pv-4bgi.css';
import '../../css/a/a3mwubgrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8pv-4bgi"/><path class="a3mwubgrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xrsh-light" /></template>
