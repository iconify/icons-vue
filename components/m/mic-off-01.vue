<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l80e67qml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l80e67qml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mic-off-01" /></template>
