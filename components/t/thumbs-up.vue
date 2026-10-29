<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxr_0bc2h.css';
import '../../css/y/yqpjzibdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxr_0bc2h wm-a"/><path class="wm-k yqpjzibdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:thumbs-up" /></template>
