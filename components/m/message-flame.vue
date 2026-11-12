<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-q62lmab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-q62lmab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-flame" /></template>
