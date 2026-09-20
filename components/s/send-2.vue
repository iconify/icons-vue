<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh5nt7b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh5nt7b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:send-2" /></template>
