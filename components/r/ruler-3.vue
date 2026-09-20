<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4ch6u7ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ch6u7ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ruler-3" /></template>
