<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpjfjpbop.css';
import '../../css/d/dqsya0j4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjfjpbop"/><path class="dqsya0j4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:muted-bold" /></template>
