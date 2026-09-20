<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtzh11bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rtzh11bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-forward-email-email-send-message-envelope-actions-action-forward-arrow" /></template>
