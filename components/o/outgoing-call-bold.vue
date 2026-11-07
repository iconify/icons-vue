<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-2vogrtb.css';
import '../../css/v/vglfn4bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-2vogrtb"/><path class="vglfn4bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-bold" /></template>
