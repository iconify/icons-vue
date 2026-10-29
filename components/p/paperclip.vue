<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx1mdyx4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx1mdyx4x wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:paperclip" /></template>
