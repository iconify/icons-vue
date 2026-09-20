<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzblx-bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzblx-bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticket-percent-filled" /></template>
