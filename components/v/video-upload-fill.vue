<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5lvuccbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5lvuccbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-upload-fill" /></template>
