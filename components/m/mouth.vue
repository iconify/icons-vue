<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rev1gzb0u.css';
import '../../css/e/etgq1od9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rev1gzb0u"/><path class="etgq1od9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mouth" /></template>
