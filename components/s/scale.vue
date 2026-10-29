<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m91g29p0v.css';
import '../../css/a/acti3litn.css';
import '../../css/s/sab5z8bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m91g29p0v wm-k"/><path class="acti3litn wm-a"/><path class="sab5z8bmm wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:scale" /></template>
