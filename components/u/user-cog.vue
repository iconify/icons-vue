<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5zor_ndn.css';
import '../../css/m/mcj8uxbod.css';
import '../../css/g/g7o_0db-i.css';
import '../../css/z/zpobyobrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5zor_ndn wm-k"/><path class="mcj8uxbod wm-k"/><path class="g7o_0db-i wm-s"/><path class="wm-s zpobyobrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:user-cog" /></template>
