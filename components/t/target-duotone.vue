<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2ew1ke.css';
import '../../css/z/znvy83hys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path clip-rule="evenodd" class="znvy83hys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:target-duotone" /></template>
