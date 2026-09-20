<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahso_0mfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahso_0mfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pass-expired-fill" /></template>
