<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwezt-ini.css';
import '../../css/k/k0vfem02x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwezt-ini"/><path class="k0vfem02x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:reply-to-message-typing-solid" /></template>
