<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8qcobdb.css';
import '../../css/i/igrd9_y7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8qcobdb"/><path clip-rule="evenodd" class="igrd9_y7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-outline" /></template>
