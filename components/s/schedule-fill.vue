<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-n0_5b8w.css';
import '../../css/l/lwm0shbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-n0_5b8w"/><path clip-rule="evenodd" class="lwm0shbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:schedule-fill" /></template>
