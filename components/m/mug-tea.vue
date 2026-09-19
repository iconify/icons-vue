<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t56w-kbog.css';
import '../../css/d/dklul-ukq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t56w-kbog"/><path class="dklul-ukq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mug-tea" /></template>
