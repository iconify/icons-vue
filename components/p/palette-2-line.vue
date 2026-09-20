<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggdj-rbkr.css';
import '../../css/d/d4aj_070k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdj-rbkr"/><circle class="d4aj_070k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-2-line" /></template>
