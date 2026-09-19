<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaxtufr3c.css';
import '../../css/f/fu72iwgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaxtufr3c"/><path class="fu72iwgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-exclamation" /></template>
