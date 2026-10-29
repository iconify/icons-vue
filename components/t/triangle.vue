<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7os6knc.css';
import '../../css/x/x8o3q-boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7os6knc"/><path class="x8o3q-boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:triangle" /></template>
