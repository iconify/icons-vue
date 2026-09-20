<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6tcy732d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6tcy732d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2" /></template>
