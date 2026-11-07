<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/m/mmtd6l_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="mmtd6l_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-square-bold-duotone" /></template>
