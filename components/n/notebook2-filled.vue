<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4-0vlbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4-0vlbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notebook2-filled" /></template>
