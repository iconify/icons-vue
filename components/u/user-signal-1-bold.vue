<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf5sz9i8w.css';
import '../../css/l/l5sm_m-zm.css';
import '../../css/g/gdubncbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf5sz9i8w"/><path class="l5sm_m-zm"/><path class="gdubncbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:user-signal-1-bold" /></template>
