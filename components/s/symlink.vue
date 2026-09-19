<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4zfxlbgj.css';
import '../../css/b/bh79t3b8l.css';
import '../../css/n/nnghyyb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a4zfxlbgj"/><path class="bh79t3b8l"/><path class="nnghyyb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:symlink" /></template>
