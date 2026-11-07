<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaqcsrbps.css';
import '../../css/e/etx3uacem.css';
import '../../css/a/ar4azzsja.css';
import '../../css/y/yk2l4-b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qaqcsrbps"/><path class="etx3uacem"/><path class="ar4azzsja"/><path class="yk2l4-b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-bold-duotone" /></template>
