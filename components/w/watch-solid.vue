<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ody6ekxva.css';
import '../../css/m/msx52gb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ody6ekxva"/><path class="msx52gb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:watch-solid" /></template>
