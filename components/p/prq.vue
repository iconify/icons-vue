<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi-ue2tqy.css';
import '../../css/m/mo_rg4g7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-ue2tqy"/><path class="mo_rg4g7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:prq" /></template>
