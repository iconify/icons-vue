<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpywgebrg.css';
import '../../css/v/v2zklq74z.css';
import '../../css/c/cg22ifrfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpywgebrg"/><path class="v2zklq74z"/><path class="cg22ifrfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-2-bold-duotone" /></template>
