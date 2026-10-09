<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1e83_bpf.css';
import '../../css/q/qmfyblb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x1e83_bpf"/><path class="qmfyblb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-medium-20-bold" /></template>
