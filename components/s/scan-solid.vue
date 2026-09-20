<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql906wbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ql906wbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:scan-solid" /></template>
