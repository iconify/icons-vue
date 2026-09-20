<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgcwpxbmf.css';
import '../../css/q/qjy94lrde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="bgcwpxbmf"/><path clip-rule="evenodd" class="qjy94lrde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:progress-duotone" /></template>
