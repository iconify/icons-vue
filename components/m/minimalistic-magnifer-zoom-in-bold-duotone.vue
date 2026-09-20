<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aygw_60rm.css';
import '../../css/o/oo3ilkkyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="oo3ilkkyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-zoom-in-bold-duotone" /></template>
