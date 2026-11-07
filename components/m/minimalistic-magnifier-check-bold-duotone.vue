<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl66i7bqg.css';
import '../../css/d/dz4pyzk-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="dz4pyzk-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-check-bold-duotone" /></template>
