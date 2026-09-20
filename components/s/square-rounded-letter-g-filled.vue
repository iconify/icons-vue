<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn4juruoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn4juruoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-g-filled" /></template>
