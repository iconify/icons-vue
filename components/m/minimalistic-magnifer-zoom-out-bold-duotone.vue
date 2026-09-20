<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygw_60rm.css';
import '../../css/d/dzoyk5cfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="dzoyk5cfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-zoom-out-bold-duotone" /></template>
