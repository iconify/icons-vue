<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl6ew7bys.css';
import '../../css/d/dt926jbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl6ew7bys wm-k"/><path class="dt926jbqr wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:reply" /></template>
