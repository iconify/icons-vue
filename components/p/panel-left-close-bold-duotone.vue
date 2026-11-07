<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9u-03p8n.css';
import '../../css/a/ar1d8pb2n.css';
import '../../css/m/muc82xbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9u-03p8n"/><path class="ar1d8pb2n"/><path class="muc82xbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-close-bold-duotone" /></template>
