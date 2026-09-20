<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0nrxghi.css';
import '../../css/v/ve2abo9wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0nrxghi"/><path class="ve2abo9wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:right-indent-alt" /></template>
