<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j896-2bez.css';
import '../../css/t/t066wzbea.css';
import '../../css/h/hrdjp705l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j896-2bez wm-k"/><path class="t066wzbea wm-a"/><path class="hrdjp705l wm-deco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rotate-cw" /></template>
