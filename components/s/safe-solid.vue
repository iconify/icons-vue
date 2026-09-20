<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_oaq9bhw.css';
import '../../css/t/t_82l-4pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_oaq9bhw"/><path clip-rule="evenodd" class="t_82l-4pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:safe-solid" /></template>
