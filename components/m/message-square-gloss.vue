<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a32mx9q6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a32mx9q6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-gloss" /></template>
