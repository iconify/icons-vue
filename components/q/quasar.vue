<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doy7itbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50.843,"height":50.843};
const content = `<path class="doy7itbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:quasar" /></template>
