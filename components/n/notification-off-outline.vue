<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcq1b5bna.css';
import '../../css/t/t5mpfkbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcq1b5bna"/><path clip-rule="evenodd" class="t5mpfkbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:notification-off-outline" /></template>
