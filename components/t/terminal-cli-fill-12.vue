<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi_go-91g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mi_go-91g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-cli-fill-12" /></template>
