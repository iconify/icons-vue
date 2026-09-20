<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7xaqs2ci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7xaqs2ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-b-filled" /></template>
