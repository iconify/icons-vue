<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfj0xfllv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfj0xfllv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize5-filled" /></template>
