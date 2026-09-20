<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjibmefbt.css';
import '../../css/r/rutj1thmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjibmefbt"/><path class="rutj1thmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moonlight-fill" /></template>
