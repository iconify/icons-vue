<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydoht-zhu.css';
import '../../css/v/v3c_7qboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydoht-zhu"/><path class="v3c_7qboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:restart-bold-duotone" /></template>
