<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bruc2q60i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bruc2q60i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-heart-gloss" /></template>
