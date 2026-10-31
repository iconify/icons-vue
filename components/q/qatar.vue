<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu52i9kgw.css';
import '../../css/x/x4jxcf4cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="pu52i9kgw"/><path class="x4jxcf4cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:qatar" /></template>
