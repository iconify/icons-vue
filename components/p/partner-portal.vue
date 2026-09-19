<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7sr6ubzr.css';
import '../../css/z/zg_xfubcu.css';
import '../../css/z/z98wavxds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7sr6ubzr"/><path class="zg_xfubcu"/><path class="z98wavxds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:partner-portal" /></template>
