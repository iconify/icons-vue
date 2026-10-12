<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf-xb_4oc.css';
import '../../css/h/h-eujcczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qf-xb_4oc"/><path class="h-eujcczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:password-20-bold" /></template>
