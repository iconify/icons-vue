<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wfgcisw.css';
import '../../css/n/nvyceb_wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i2wfgcisw"/><path class="nvyceb_wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:undo-right-round-bold-duotone" /></template>
