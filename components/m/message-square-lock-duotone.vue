<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjb3sybwq.css';
import '../../css/p/py2pseb_g.css';
import '../../css/b/bully7omt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pjb3sybwq"/><path class="py2pseb_g"/><path class="bully7omt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-lock-duotone" /></template>
