<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh620fbwj.css';
import '../../css/d/dcd3u2sfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rh620fbwj"/><path clip-rule="evenodd" class="dcd3u2sfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:navigation-compass-16" /></template>
