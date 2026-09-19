<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nak3qzbrx.css';
import '../../css/r/ryyszgs8i.css';
import '../../css/a/amqeczbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nak3qzbrx"/><path class="ryyszgs8i"/><path class="amqeczbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:seat" /></template>
