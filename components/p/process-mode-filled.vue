<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8tgkgbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j8tgkgbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:process-mode-filled" /></template>
