<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgoay3b5b.css';
import '../../css/r/r9cdxubdv.css';
import '../../css/s/sm4hol1wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgoay3b5b"/><path class="r9cdxubdv"/><path class="sm4hol1wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:taking-pictures-circle" /></template>
