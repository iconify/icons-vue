<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhf44wb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhf44wb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:navigation-07" /></template>
