<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5s7lcbme.css';
import '../../css/p/phlx78bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5s7lcbme"/><path class="phlx78bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tag-state-filled" /></template>
