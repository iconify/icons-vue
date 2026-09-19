<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s07htpbtb.css';
import '../../css/v/vslx-5blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s07htpbtb"/><path class="vslx-5blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:safe-filled" /></template>
