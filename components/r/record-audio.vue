<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a15vrjyzh.css';
import '../../css/f/fwgabzb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="a15vrjyzh"/><path class="fwgabzb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:record-audio" /></template>
