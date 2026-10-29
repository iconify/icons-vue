<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mti05vejb.css';
import '../../css/q/qxq52ip6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mti05vejb"/><path class="qxq52ip6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:tooth" /></template>
