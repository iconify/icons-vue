<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9bapbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li9bapbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-u-filled" /></template>
