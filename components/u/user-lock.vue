<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dmvc1yldm.css';
import '../../css/n/nb8oh8imn.css';
import '../../css/a/at7owu2sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dmvc1yldm wm-k"/><path class="nb8oh8imn wm-s"/><path class="at7owu2sk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:user-lock" /></template>
