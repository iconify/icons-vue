<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlyrpgbor.css';
import '../../css/u/u7_wj4bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlyrpgbor"/><path class="u7_wj4bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:weigher-bold-duotone" /></template>
