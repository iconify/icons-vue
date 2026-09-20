<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwisqacpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwisqacpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-check-filled" /></template>
