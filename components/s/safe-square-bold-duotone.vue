<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_frcb-c.css';
import '../../css/o/oxd2n2_mg.css';
import '../../css/r/rwsejcbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_frcb-c"/><path class="oxd2n2_mg"/><path clip-rule="evenodd" class="rwsejcbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-square-bold-duotone" /></template>
