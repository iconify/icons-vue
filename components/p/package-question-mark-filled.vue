<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldqp-hbll.css';
import '../../css/g/ghz_-ebeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldqp-hbll"/><path class="ghz_-ebeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:package-question-mark-filled" /></template>
