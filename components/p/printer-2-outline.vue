<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myod-k65i.css';
import '../../css/i/ihkre-bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myod-k65i"/><path class="ihkre-bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-2-outline" /></template>
