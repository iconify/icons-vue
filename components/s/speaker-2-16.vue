<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt9b-hb6i.css';
import '../../css/e/esks6_bvk.css';
import '../../css/h/hgxtv_kog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rt9b-hb6i"/><path clip-rule="evenodd" class="esks6_bvk"/><path class="hgxtv_kog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:speaker-2-16" /></template>
