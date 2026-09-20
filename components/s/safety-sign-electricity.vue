<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu4c-gk5y.css';
import '../../css/b/b76l5ee_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4c-gk5y"/><path class="b76l5ee_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:safety-sign-electricity" /></template>
