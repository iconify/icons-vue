<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bsc_-kbyb.css';
import '../../css/e/ec1r3sx7z.css';
import '../../css/l/ldv_q5b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsc_-kbyb"/><path class="ec1r3sx7z"/><path class="ldv_q5b1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:monocle-01" /></template>
