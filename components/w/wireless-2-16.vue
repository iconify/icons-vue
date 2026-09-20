<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2sp9xloz.css';
import '../../css/c/cg9on-ftx.css';
import '../../css/s/swaugsbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2sp9xloz"/><path class="cg9on-ftx"/><path class="swaugsbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wireless-2-16" /></template>
