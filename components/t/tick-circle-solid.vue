<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymlmo2owc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ymlmo2owc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tick-circle-solid" /></template>
