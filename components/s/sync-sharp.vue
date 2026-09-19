<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqmmymb5e.css';
import '../../css/f/fy2fydtce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqmmymb5e"/><path class="fy2fydtce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:sync-sharp" /></template>
