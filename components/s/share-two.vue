<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvbgy_bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lvbgy_bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:share-two" /></template>
