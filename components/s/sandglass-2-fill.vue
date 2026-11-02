<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/regq6rblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="regq6rblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandglass-2-fill" /></template>
