<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j43vdgeku.css';
import '../../css/a/aevd0o1gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j43vdgeku"/><path class="aevd0o1gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-detail" /></template>
