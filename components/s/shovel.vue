<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/fip4tbboc.css';
import '../../css/h/h_eof1loy.css';
import '../../css/t/tmtoxorob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="fip4tbboc"/><path class="h_eof1loy"/><path class="tmtoxorob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shovel" /></template>
