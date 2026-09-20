<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw5u4miyi.css';
import '../../css/b/b2dxt0bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5u4miyi"/><path class="b2dxt0bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:paper-write-bold" /></template>
