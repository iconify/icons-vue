<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpyifib8k.css';
import '../../css/i/irp5xvbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpyifib8k"/><path class="irp5xvbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:phone-log-filled" /></template>
