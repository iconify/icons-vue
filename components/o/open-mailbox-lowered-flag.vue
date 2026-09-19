<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kayvkbc6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kayvkbc6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:open-mailbox-lowered-flag" /></template>
