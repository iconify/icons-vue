<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8n6hxosg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="b8n6hxosg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-waiting" /></template>
