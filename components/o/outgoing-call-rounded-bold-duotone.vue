<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx1qmxb2o.css';
import '../../css/s/s02o69bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx1qmxb2o"/><path class="s02o69bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:outgoing-call-rounded-bold-duotone" /></template>
