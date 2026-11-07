<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajy_v4bwf.css';
import '../../css/h/h9vo8yb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajy_v4bwf"/><path clip-rule="evenodd" class="h9vo8yb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-minimalistic-bold" /></template>
