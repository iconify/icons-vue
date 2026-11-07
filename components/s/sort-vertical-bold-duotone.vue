<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl8qmubzh.css';
import '../../css/q/qwd-pmblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8qmubzh"/><path class="qwd-pmblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-vertical-bold-duotone" /></template>
