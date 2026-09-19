<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns3mynbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ns3mynbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:open-mailbox-raised-flag" /></template>
