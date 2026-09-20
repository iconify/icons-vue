<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d0c44qvfi.css';
import '../../css/t/tyb-udb1w.css';
import '../../css/o/ooqomeb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d0c44qvfi"/><path class="tyb-udb1w"/><path class="ooqomeb9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:mobilephone-action-lock" /></template>
