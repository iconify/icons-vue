<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxpwkkx4b.css';
import '../../css/c/cxrhsobiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oxpwkkx4b"/><path clip-rule="evenodd" class="cxrhsobiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:whatsapp-solid" /></template>
