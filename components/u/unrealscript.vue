<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niwz-lbqb.css';
import '../../css/b/buiu9ebyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="niwz-lbqb"/><path class="buiu9ebyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:unrealscript" /></template>
