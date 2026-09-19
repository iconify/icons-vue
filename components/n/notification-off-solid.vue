<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se48-pe8k.css';
import '../../css/r/repczfbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se48-pe8k"/><path clip-rule="evenodd" class="repczfbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:notification-off-solid" /></template>
