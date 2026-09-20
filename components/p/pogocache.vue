<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwp6cxbin.css';
import '../../css/t/t5vikhbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwp6cxbin"/><path class="t5vikhbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pogocache" /></template>
