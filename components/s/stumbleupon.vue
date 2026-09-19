<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ijmfbcv.css';
import '../../css/d/dj_p1sbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v4ijmfbcv"/><path class="dj_p1sbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:stumbleupon" /></template>
