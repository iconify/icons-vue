<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dojiukb8c.css';
import '../../css/u/u1_hubbvw.css';
import '../../css/w/wk2zli15y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dojiukb8c wm-k"/><path class="u1_hubbvw wm-a"/><path class="wk2zli15y wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:passport" /></template>
