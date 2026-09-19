<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-rtspsnc.css';
import '../../css/o/owdlqbbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l-rtspsnc"/><path class="owdlqbbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:quote-fill-12" /></template>
