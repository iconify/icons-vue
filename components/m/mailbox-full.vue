<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iikr6dbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iikr6dbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mailbox-full" /></template>
