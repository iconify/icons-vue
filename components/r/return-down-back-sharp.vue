<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0jdfibba.css';
import '../../css/o/oidh77b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0jdfibba"/><path class="oidh77b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:return-down-back-sharp" /></template>
