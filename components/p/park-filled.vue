<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng1qcuzik.css';
import '../../css/k/kt2s0db6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1qcuzik"/><path class="kt2s0db6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:park-filled" /></template>
