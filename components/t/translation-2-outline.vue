<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u99antbvu.css';
import '../../css/s/sby6-kb3l.css';
import '../../css/z/z9sww47-j.css';
import '../../css/z/zreo3t4eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u99antbvu"/><path class="sby6-kb3l"/><path clip-rule="evenodd" class="z9sww47-j"/><path clip-rule="evenodd" class="zreo3t4eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-2-outline" /></template>
