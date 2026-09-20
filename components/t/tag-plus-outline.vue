<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijh1c3bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijh1c3bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-plus-outline" /></template>
