<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d290v0skq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d290v0skq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:soundcloud-logo-block" /></template>
