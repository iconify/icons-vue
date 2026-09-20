<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgdiet0qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgdiet0qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-u-filled" /></template>
