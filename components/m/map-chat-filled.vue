<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw5gyubsx.css';
import '../../css/j/jjcq2bbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw5gyubsx"/><path class="jjcq2bbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-chat-filled" /></template>
