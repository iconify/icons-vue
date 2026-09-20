<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtk_9ha-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qtk_9ha-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:message-minus-outline" /></template>
