<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqpby_sqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqpby_sqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pharagraphspacing-filled" /></template>
