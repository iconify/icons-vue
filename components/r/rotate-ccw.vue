<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx14ww5ye.css';
import '../../css/v/vje-gkoqo.css';
import '../../css/h/hrdjp705l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx14ww5ye wm-k"/><path class="vje-gkoqo wm-a"/><path class="hrdjp705l wm-deco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:rotate-ccw" /></template>
