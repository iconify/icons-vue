<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l03ivrben.css';
import '../../css/w/wlmt3rjgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l03ivrben"/><path class="wlmt3rjgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mountain-view" /></template>
