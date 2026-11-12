<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz_svobux.css';
import '../../css/h/h6ro5gj3z.css';
import '../../css/m/mmux6pkuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wz_svobux"/><path class="h6ro5gj3z"/><path class="mmux6pkuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-forms-dark" /></template>
