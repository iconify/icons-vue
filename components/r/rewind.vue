<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxonx6bxn.css';
import '../../css/g/gu-ybwb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxonx6bxn"/><path class="gu-ybwb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rewind" /></template>
