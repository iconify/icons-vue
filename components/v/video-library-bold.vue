<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3_gtob6t.css';
import '../../css/b/bz0qnvbjd.css';
import '../../css/x/xc6fu6b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3_gtob6t"/><path class="bz0qnvbjd"/><path clip-rule="evenodd" class="xc6fu6b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-library-bold" /></template>
