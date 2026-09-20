<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o90f_1ibj.css';
import '../../css/t/t33cxfb4q.css';
import '../../css/z/z4nxktxkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o90f_1ibj"/><path class="t33cxfb4q"/><path class="z4nxktxkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:many-notes" /></template>
