<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr8nxob_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tr8nxob_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rndr" /></template>
