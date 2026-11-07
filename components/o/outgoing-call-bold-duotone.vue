<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx1qmxb2o.css';
import '../../css/j/j05r12o9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx1qmxb2o"/><path class="j05r12o9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-bold-duotone" /></template>
