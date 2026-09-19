<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0xpv8ejv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0xpv8ejv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-alt-edit" /></template>
