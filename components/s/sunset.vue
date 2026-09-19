<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek9_zcc6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek9_zcc6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:sunset" /></template>
