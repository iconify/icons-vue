<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teos6bbsl.css';
import '../../css/a/at11vggis.css';
import '../../css/s/s-klz88_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teos6bbsl"/><path class="at11vggis"/><path class="s-klz88_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:ollama" /></template>
