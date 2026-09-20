<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eex20wb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eex20wb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-bolt" /></template>
