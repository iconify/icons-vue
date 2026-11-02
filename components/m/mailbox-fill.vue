<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awvoz5hrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awvoz5hrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mailbox-fill" /></template>
