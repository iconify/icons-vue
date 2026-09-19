<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwghczbgl.css';
import '../../css/u/uh-uk-b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwghczbgl"/><path class="uh-uk-b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trip-filled" /></template>
