<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olzswx62l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olzswx62l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-fill-round" /></template>
