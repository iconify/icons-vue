<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7ssc3b8h.css';
import '../../css/z/zo3cxx6gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="i7ssc3b8h"/><path clip-rule="evenodd" class="zo3cxx6gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-bold-duotone" /></template>
