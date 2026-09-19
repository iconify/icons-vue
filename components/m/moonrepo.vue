<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f87i2j8hs.css';
import '../../css/b/bo_tdpbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f87i2j8hs"/><circle class="bo_tdpbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:moonrepo" /></template>
