<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaizi48jf.css';
import '../../css/y/yrprrjbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path clip-rule="evenodd" class="yrprrjbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-keyhole-minimalistic-bold-duotone" /></template>
