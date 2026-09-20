<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6u5tubte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z6u5tubte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-switch-account-solid" /></template>
