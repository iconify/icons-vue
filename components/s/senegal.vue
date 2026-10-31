<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xytt3obod.css';
import '../../css/j/j10uc_vjr.css';
import '../../css/v/v4wa-kb6k.css';
import '../../css/d/dbvk5x3la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="xytt3obod"/><path class="j10uc_vjr"/><path class="v4wa-kb6k"/><path class="dbvk5x3la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:senegal" /></template>
