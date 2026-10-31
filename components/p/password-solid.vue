<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z361xccom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z361xccom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-solid" /></template>
