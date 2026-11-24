<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxigcqtgr.css';
import '../../css/r/r2mnmqlht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxigcqtgr"/><path class="r2mnmqlht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:store-filled" /></template>
