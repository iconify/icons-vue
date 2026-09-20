<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmlt0ibsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="xmlt0ibsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:screen-normal" /></template>
