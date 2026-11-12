<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9g__ikfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9g__ikfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-share" /></template>
