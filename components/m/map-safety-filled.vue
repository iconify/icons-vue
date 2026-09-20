<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9orhbcrs.css';
import '../../css/b/bye6f4hdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9orhbcrs"/><path class="bye6f4hdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-safety-filled" /></template>
