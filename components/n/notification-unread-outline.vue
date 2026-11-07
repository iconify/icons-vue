<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vheb2-beq.css';
import '../../css/u/ubakjmb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vheb2-beq"/><path clip-rule="evenodd" class="ubakjmb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notification-unread-outline" /></template>
