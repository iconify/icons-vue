<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx1qtac8g.css';
import '../../css/w/wkho5gbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx1qtac8g"/><path class="wkho5gbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mailbox-empty-duotone" /></template>
