<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrj1g3mhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrj1g3mhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:transform-3" /></template>
