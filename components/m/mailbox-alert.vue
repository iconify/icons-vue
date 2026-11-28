<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-gqurbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-gqurbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mailbox-alert" /></template>
