<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j07dkobur.css';
import '../../css/s/ssl_p8bbq.css';
import '../../css/v/vzr5kgc6d.css';
import '../../css/l/lcu8a2auw.css';
import '../../css/e/e4lgkbr8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j07dkobur"/><path class="ssl_p8bbq"/><path class="vzr5kgc6d"/><path class="lcu8a2auw"/><path class="e4lgkbr8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:website-development-browser-source-code" /></template>
