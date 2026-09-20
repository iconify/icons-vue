<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bguki9bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bguki9bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-horizontal-sharp" /></template>
