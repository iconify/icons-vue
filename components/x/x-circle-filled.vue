<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh3id2b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oh3id2b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:x-circle-filled" /></template>
