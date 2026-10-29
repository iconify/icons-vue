<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/k/k48bdwq9n.css';
import '../../css/g/ge5djsb-y.css';
import '../../css/w/whli9vrlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="k48bdwq9n"/><path class="ge5djsb-y"/><path class="whli9vrlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:message-circle-question" /></template>
