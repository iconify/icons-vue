<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv2ndra2q.css';
import '../../css/m/mgbb3achs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2ndra2q"/><path class="mgbb3achs wm-deco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:moon" /></template>
