<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3_gtob6t.css';
import '../../css/b/bz0qnvbjd.css';
import '../../css/z/zoz5x5bue.css';
import '../../css/i/io_i03bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="bz0qnvbjd"/><path class="zoz5x5bue"/><path clip-rule="evenodd" class="io_i03bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-library-2-bold" /></template>
