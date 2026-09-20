<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pra9yqb_a.css';
import '../../css/h/hu1yjobuk.css';
import '../../css/g/g_-f5xbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pra9yqb_a"/><path class="hu1yjobuk"/><path class="g_-f5xbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:voice-id-approved" /></template>
