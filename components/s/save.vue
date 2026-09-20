<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0fw8pbdn.css';
import '../../css/r/rkj0d4ldk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0fw8pbdn"/><path class="rkj0d4ldk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:save" /></template>
