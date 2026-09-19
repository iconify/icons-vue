<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmiv43pty.css';
import '../../css/z/zpbo7acvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmiv43pty"/><path class="zpbo7acvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:rocket-sharp" /></template>
