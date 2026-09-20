<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8fshfj-z.css';
import '../../css/n/nmroajm4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8fshfj-z"/><path clip-rule="evenodd" class="nmroajm4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toilet-paper-fill" /></template>
