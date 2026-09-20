<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjvh8st1n.css';
import '../../css/x/xmtno77zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gjvh8st1n"/><path class="xmtno77zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:mri-pet" /></template>
