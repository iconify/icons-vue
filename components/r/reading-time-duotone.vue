<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnnw44bzb.css';
import '../../css/q/q810p6bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnnw44bzb"/><path class="q810p6bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:reading-time-duotone" /></template>
