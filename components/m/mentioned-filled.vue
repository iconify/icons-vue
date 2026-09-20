<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fom46j_ot.css';
import '../../css/e/en5_3bbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fom46j_ot"/><path class="en5_3bbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mentioned-filled" /></template>
