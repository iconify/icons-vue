<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6a9xhbrm.css';
import '../../css/x/x8n4ul95g.css';
import '../../css/k/ksc_xx8rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6a9xhbrm"/><path class="x8n4ul95g"/><path class="ksc_xx8rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safe-48-bold" /></template>
