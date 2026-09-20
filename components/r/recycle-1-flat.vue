<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brwsvfk3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brwsvfk3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:recycle-1-flat" /></template>
