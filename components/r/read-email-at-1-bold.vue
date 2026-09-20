<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdmk0nb5w.css';
import '../../css/l/loieh1tve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdmk0nb5w"/><path class="loieh1tve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:read-email-at-1-bold" /></template>
