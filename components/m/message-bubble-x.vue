<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn39bsb7i.css';
import '../../css/a/aevd0o1gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn39bsb7i"/><path class="aevd0o1gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-x" /></template>
