<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx2002bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx2002bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rss" /></template>
