<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx9l9-clq.css';
import '../../css/y/yfq3bynsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx9l9-clq"/><path class="yfq3bynsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-bold-duotone" /></template>
