<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwrj1ekre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dwrj1ekre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shell-window-maximize-filled" /></template>
