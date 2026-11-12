<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kytdf289u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kytdf289u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-spark" /></template>
