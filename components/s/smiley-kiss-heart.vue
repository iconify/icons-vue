<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atebddbcx.css';
import '../../css/o/odo83i1su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atebddbcx"/><path class="odo83i1su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-kiss-heart" /></template>
