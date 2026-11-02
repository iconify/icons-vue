<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it89dpbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it89dpbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rest-area-fill" /></template>
