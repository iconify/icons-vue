<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpt-vi5dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpt-vi5dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quiet-chat-dark" /></template>
