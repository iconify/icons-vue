<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aboskhb3q.css';
import '../../css/h/hie0ikbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aboskhb3q"/><path class="hie0ikbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:prometheus-wordmark" /></template>
