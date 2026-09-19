<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bng3m8b7n.css';
import '../../css/y/yy-od7caa.css';
import '../../css/o/om051pb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bng3m8b7n"/><circle class="yy-od7caa"/><path class="om051pb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:voice-presentation" /></template>
