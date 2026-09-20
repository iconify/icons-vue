<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3suf8dlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3suf8dlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-zero-or-one-to-zero-or-many" /></template>
