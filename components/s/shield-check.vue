<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aioi5mbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aioi5mbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-check" /></template>
