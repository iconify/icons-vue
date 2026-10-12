<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt5vbccxc.css';
import '../../css/s/s6t1fwbej.css';
import '../../css/f/f57g08bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tt5vbccxc"/><path class="s6t1fwbej"/><path class="f57g08bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:router-filled" /></template>
