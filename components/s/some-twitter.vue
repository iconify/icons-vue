<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_p1xvlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_p1xvlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-twitter" /></template>
