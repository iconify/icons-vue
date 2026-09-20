<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7bn6nb8f.css';
import '../../css/i/izn9dcbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7bn6nb8f"/><path class="izn9dcbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unmute-24" /></template>
