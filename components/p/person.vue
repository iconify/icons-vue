<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shvlg_s5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="shvlg_s5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:person" /></template>
