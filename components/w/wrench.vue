<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo_9irb0d.css';
import '../../css/l/l6wodwbos.css';
import '../../css/s/siajtsbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo_9irb0d"/><path class="l6wodwbos"/><path class="siajtsbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:wrench" /></template>
