<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm9sh3z2f.css';
import '../../css/j/j319albkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xm9sh3z2f"/><path class="j319albkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-stroke-20" /></template>
