<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjpq_osli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bjpq_osli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stop-fill" /></template>
