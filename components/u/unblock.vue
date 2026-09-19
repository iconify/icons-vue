<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt40imznw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt40imznw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:unblock" /></template>
