<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6304ibce.css';
import '../../css/a/aygw_60rm.css';
import '../../css/q/qntnbrb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6304ibce"/><path class="aygw_60rm"/><path clip-rule="evenodd" class="qntnbrb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-bug-bold-duotone" /></template>
