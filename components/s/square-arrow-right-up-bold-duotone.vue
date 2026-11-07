<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0tkg9bgp.css';
import '../../css/p/pbv_9xbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0tkg9bgp"/><path class="pbv_9xbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-right-up-bold-duotone" /></template>
