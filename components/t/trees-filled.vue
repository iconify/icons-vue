<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf-n3jbtm.css';
import '../../css/p/p2xw8f0_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf-n3jbtm"/><path class="p2xw8f0_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:trees-filled" /></template>
