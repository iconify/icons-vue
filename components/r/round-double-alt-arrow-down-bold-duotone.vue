<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c77vne7ui.css';
import '../../css/w/w177c5zkh.css';
import '../../css/n/nidoksbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c77vne7ui"/><path class="w177c5zkh"/><path class="nidoksbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-double-alt-arrow-down-bold-duotone" /></template>
