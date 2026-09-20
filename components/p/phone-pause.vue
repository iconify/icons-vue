<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls9cc-bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls9cc-bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-pause" /></template>
